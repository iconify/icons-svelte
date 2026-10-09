<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhkg43b8y.css';
import '../../css/b/bxrez7b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nhkg43b8y"/><path class="bxrez7b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ice-cream-20" {...props}></Icon>
