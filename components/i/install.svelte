<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew8xs4bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ew8xs4bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:install" {...props}></Icon>
