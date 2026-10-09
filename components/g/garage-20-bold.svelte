<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlqdhacda.css';
import '../../css/o/ojpm0hbkb.css';
import '../../css/p/p7necabgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xlqdhacda"/><path class="ojpm0hbkb"/><path class="p7necabgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:garage-20-bold" {...props}></Icon>
