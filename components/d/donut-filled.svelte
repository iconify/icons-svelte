<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptc-d2h3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptc-d2h3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:donut-filled" {...props}></Icon>
