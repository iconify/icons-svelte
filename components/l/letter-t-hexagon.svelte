<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha3hny2-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha3hny2-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-t-hexagon" {...props}></Icon>
