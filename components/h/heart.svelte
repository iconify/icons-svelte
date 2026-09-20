<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk0b5pbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bk0b5pbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:heart" {...props}></Icon>
