<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6t120hgc.css';
import '../../css/z/zln2gxb3r.css';
import '../../css/f/fq33uibus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6t120hgc"/><path class="zln2gxb3r"/><path class="fq33uibus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-plus-20-bold" {...props}></Icon>
