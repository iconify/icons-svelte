<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et01rkb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et01rkb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery-warning" {...props}></Icon>
