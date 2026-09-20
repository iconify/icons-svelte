<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf1ps_r9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hf1ps_r9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:brand-zoom" {...props}></Icon>
