<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2e05bcja.css';
import '../../css/j/juj0211vf.css';
import '../../css/z/zpr4ze31r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d2e05bcja"/><path class="juj0211vf"/><path class="zpr4ze31r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:colota-light" {...props}></Icon>
