<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juj97tbkw.css';
import '../../css/l/lsr8k0bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="juj97tbkw"/><path class="lsr8k0bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hanger-20" {...props}></Icon>
