<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfkb007lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfkb007lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:fruit-banana-bold" {...props}></Icon>
