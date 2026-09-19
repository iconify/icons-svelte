<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjhtbdckh.css';
import '../../css/a/a7ajif61p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yjhtbdckh"/><circle class="a7ajif61p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:eye-outline" {...props}></Icon>
