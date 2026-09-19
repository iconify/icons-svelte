<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4j_jjn9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4j_jjn9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:play-circle" {...props}></Icon>
