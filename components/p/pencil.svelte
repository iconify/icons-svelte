<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsvs-7g4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qsvs-7g4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:pencil" {...props}></Icon>
