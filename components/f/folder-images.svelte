<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4160sb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h4160sb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:folder-images" {...props}></Icon>
