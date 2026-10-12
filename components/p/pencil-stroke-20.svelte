<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3fa6r4bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q3fa6r4bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pencil-stroke-20" {...props}></Icon>
