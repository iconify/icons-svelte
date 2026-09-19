<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5ey9xbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="a5ey9xbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:crown" {...props}></Icon>
