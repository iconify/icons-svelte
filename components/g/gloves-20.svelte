<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb5l6nbqc.css';
import '../../css/u/u6mkpijxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fb5l6nbqc"/><path class="u6mkpijxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gloves-20" {...props}></Icon>
