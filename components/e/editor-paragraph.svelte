<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xey49acws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xey49acws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-paragraph" {...props}></Icon>
