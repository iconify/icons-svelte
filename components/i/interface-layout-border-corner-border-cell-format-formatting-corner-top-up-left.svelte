<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3tf_jmrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s3tf_jmrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-layout-border-corner-border-cell-format-formatting-corner-top-up-left" {...props}></Icon>
