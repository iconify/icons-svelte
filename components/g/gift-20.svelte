<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i43p6u3yo.css';
import '../../css/t/tp2nuligo.css';
import '../../css/v/vsr49z78k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i43p6u3yo"/><path class="tp2nuligo"/><path class="vsr49z78k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gift-20" {...props}></Icon>
