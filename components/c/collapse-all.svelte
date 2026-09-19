<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_-qmpv3t.css';
import '../../css/w/w-fhuabts.css';
import '../../css/v/vnkf6_bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w_-qmpv3t"/><path class="w-fhuabts"/><path class="vnkf6_bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:collapse-all" {...props}></Icon>
