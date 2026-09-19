<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-i64oi4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-i64oi4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:futhark" {...props}></Icon>
