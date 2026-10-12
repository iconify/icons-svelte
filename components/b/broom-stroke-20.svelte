<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6cypmbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u6cypmbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:broom-stroke-20" {...props}></Icon>
