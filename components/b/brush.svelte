<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0opfxbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g0opfxbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:brush" {...props}></Icon>
