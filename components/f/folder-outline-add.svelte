<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahz_e6bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ahz_e6bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:folder-outline-add" {...props}></Icon>
