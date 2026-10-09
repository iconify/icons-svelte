<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ndo13-j.css';
import '../../css/t/tyb8w2bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o1ndo13-j"/><path class="tyb8w2bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bread-20-bold" {...props}></Icon>
