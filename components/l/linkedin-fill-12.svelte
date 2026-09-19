<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv_n7dmdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kv_n7dmdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:linkedin-fill-12" {...props}></Icon>
