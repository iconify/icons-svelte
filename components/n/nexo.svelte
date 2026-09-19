<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6-hb5m7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p6-hb5m7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nexo" {...props}></Icon>
