<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv22t_oag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kv22t_oag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gitter" {...props}></Icon>
