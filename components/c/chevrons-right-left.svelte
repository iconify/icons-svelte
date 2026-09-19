<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1nh22q4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1nh22q4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chevrons-right-left" {...props}></Icon>
