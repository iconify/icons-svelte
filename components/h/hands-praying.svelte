<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh7z1bckc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qh7z1bckc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hands-praying" {...props}></Icon>
