<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5s0_hb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":180,"height":180};
const content = `<path paint-order="fill markers stroke" class="l5s0_hb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:adonis" {...props}></Icon>
