<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itgfgib5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itgfgib5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-calling" {...props}></Icon>
