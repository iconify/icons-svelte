<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1y-5hb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1y-5hb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-right-square-filled" {...props}></Icon>
