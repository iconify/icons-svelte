<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv9k0bb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xv9k0bb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:clipboard-check" {...props}></Icon>
