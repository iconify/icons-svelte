<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ario1abrj.css';
import '../../css/f/fi8t2tb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ario1abrj"/><path class="fi8t2tb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:barrel-20-bold" {...props}></Icon>
