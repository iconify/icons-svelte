<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpwlrrj0w.css';
import '../../css/f/f1-j5o70g.css';
import '../../css/j/jzpmabcry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jpwlrrj0w"/><path class="f1-j5o70g"/><path class="jzpmabcry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:manganese-20-bold" {...props}></Icon>
