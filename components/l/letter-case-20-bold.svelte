<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6ofuubxb.css';
import '../../css/a/aw4zs_blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6ofuubxb"/><path class="aw4zs_blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:letter-case-20-bold" {...props}></Icon>
