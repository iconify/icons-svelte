<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq7y_cb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fq7y_cb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:alt-text" {...props}></Icon>
