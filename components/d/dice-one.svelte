<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc489ewpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xc489ewpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:dice-one" {...props}></Icon>
