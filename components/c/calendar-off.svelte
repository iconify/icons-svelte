<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk7l_pq-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk7l_pq-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-off" {...props}></Icon>
