<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs66_p_pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zs66_p_pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:fast-backward" {...props}></Icon>
