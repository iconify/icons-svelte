<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg0ptgbvl.css';
import '../../css/y/y6o2cyb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eg0ptgbvl"/><path class="y6o2cyb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:notebook" {...props}></Icon>
