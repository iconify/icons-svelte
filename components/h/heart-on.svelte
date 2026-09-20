<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9nik1b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9nik1b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:heart-on" {...props}></Icon>
