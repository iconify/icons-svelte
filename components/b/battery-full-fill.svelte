<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux2ta2kwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux2ta2kwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:battery-full-fill" {...props}></Icon>
