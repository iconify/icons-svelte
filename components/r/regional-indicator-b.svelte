<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnkwc0bul.css';
import '../../css/b/bc5-xubfs.css';
import '../../css/s/sk_bn9biv.css';
import '../../css/u/u3l-wgboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="qnkwc0bul"/><g class="bc5-xubfs"><circle class="sk_bn9biv"/><path class="u3l-wgboc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:regional-indicator-b" {...props}></Icon>
