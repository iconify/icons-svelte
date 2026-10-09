<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr3bl6b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cr3bl6b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caret-left-20-bold" {...props}></Icon>
