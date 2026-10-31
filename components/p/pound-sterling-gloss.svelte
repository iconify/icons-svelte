<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l885mrb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l885mrb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pound-sterling-gloss" {...props}></Icon>
