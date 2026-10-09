<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6xwa879m.css';
import '../../css/i/i1hgre67m.css';
import '../../css/s/srewe004d.css';
import '../../css/j/jrsb6f_rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a6xwa879m"/><path class="i1hgre67m"/><path class="srewe004d"/><path class="jrsb6f_rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pizza-oven-20" {...props}></Icon>
