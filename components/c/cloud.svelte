<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yukihcwxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yukihcwxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud" {...props}></Icon>
