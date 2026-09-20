<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g01t5fb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g01t5fb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:amd-logo" {...props}></Icon>
