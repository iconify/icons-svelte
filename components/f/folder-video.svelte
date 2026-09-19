<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoh5rg3zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uoh5rg3zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:folder-video" {...props}></Icon>
