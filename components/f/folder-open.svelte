<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoayjgb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yoayjgb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:folder-open" {...props}></Icon>
