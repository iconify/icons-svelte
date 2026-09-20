<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ctvfujo.css';
import '../../css/q/q00bcy-qc.css';
import '../../css/j/jv2czo-4r.css';
import '../../css/z/z8onmlb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m4ctvfujo"/><path class="q00bcy-qc"/><path class="jv2czo-4r"/><path class="z8onmlb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-close-book-bookmark" {...props}></Icon>
