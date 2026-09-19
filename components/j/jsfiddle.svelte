<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omgkdvbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1408};
const content = `<path class="omgkdvbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:jsfiddle" {...props}></Icon>
