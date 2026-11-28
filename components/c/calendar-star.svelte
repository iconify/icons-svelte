<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0sa_sb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0sa_sb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-star" {...props}></Icon>
