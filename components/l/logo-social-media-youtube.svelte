<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjsut2bzf.css';
import '../../css/x/x8-n8yhcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jjsut2bzf"/><path class="x8-n8yhcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-social-media-youtube" {...props}></Icon>
