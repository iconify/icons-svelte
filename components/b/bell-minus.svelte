<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnhz1hbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnhz1hbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bell-minus" {...props}></Icon>
