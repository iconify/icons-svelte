<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pepp-t52r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pepp-t52r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-half-stroke-20" {...props}></Icon>
