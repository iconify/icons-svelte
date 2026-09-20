<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wusoxkb0r.css';
import '../../css/y/yu8tkqs3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wusoxkb0r"/><path class="yu8tkqs3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:medium-dark-skin-tone" {...props}></Icon>
