<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi70slb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qi70slb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:o" {...props}></Icon>
