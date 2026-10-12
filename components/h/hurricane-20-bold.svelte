<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0h02gu-q.css';
import '../../css/z/zfr7hdc4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r0h02gu-q"/><path class="zfr7hdc4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hurricane-20-bold" {...props}></Icon>
