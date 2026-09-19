<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjh781b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="zjh781b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:blood-drop" {...props}></Icon>
