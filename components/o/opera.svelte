<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzkjo4q4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzkjo4q4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:opera" {...props}></Icon>
