<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmvotg30c.css';
import '../../css/f/f1ijkjbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mmvotg30c"/><path class="f1ijkjbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:license-draft" {...props}></Icon>
