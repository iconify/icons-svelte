<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2pb8ubfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2pb8ubfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dollar-fill" {...props}></Icon>
