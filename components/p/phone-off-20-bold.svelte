<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8o5orx4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d8o5orx4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-off-20-bold" {...props}></Icon>
