<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dybeleg8o.css';
import '../../css/l/lxih1s-hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dybeleg8o"/><path class="lxih1s-hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-requirements" {...props}></Icon>
