<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4bl5-b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4bl5-b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bag-remove" {...props}></Icon>
