<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_wi9y41m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p_wi9y41m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:austral-sign" {...props}></Icon>
