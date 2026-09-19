<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4ing4w0e.css';
import '../../css/j/jqvw4p60w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="v4ing4w0e"/><path class="jqvw4p60w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:refresh" {...props}></Icon>
