<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj21nobix.css';
import '../../css/l/lt2ak2b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aj21nobix"/><path class="lt2ak2b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pedestrian-family" {...props}></Icon>
