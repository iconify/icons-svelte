<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww4fyqbuj.css';
import '../../css/w/wy7ugsoed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ww4fyqbuj"/><path class="wy7ugsoed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-dizzy" {...props}></Icon>
