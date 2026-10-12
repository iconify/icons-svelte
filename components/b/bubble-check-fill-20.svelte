<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng6032t4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ng6032t4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubble-check-fill-20" {...props}></Icon>
