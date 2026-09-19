<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy-hsnmqc.css';
import '../../css/f/f1ijkjbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sy-hsnmqc"/><path class="f1ijkjbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:license-third-party-draft" {...props}></Icon>
