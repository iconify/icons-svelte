<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap4qq9qms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="ap4qq9qms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-size" {...props}></Icon>
