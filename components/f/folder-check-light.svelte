<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shu_wxu_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="shu_wxu_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:folder-check-light" {...props}></Icon>
