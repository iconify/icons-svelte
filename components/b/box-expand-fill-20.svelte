<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ann_yxbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ann_yxbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:box-expand-fill-20" {...props}></Icon>
