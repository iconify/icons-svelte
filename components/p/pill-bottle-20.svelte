<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0g24_-dr.css';
import '../../css/n/nodo6_-it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s0g24_-dr"/><path class="nodo6_-it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pill-bottle-20" {...props}></Icon>
