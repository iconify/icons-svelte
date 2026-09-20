<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sng5_6bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sng5_6bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-left-square-fill" {...props}></Icon>
