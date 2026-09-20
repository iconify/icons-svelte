<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx9mnmbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yx9mnmbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-link" {...props}></Icon>
