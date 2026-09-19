<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe6v-xfxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pe6v-xfxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:corn" {...props}></Icon>
