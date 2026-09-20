<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf7uc5zzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rf7uc5zzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:inbox-download" {...props}></Icon>
