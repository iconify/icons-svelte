<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkrilib-s.css';
import '../../css/d/dh5-_5bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkrilib-s"/><path clip-rule="evenodd" class="dh5-_5bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:movie" {...props}></Icon>
