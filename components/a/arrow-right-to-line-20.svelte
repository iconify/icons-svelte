<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3z3e5bjw.css';
import '../../css/q/qqzqv2f4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u3z3e5bjw"/><path class="qqzqv2f4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-to-line-20" {...props}></Icon>
