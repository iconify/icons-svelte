<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdnkc-v7d.css';
import '../../css/p/pd8vq-blm.css';
import '../../css/u/u0ofk_h1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fdnkc-v7d"/><path class="pd8vq-blm"/><path class="u0ofk_h1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:function" {...props}></Icon>
