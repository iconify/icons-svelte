<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl9p_ccsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tl9p_ccsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:gender-neutral-user" {...props}></Icon>
