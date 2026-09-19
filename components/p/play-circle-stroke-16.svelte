<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upo67d98k.css';
import '../../css/i/ikh678xfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="upo67d98k"/><path class="ikh678xfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:play-circle-stroke-16" {...props}></Icon>
