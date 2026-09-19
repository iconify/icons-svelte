<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvyj2k6nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zvyj2k6nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:placemark" {...props}></Icon>
