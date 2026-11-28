<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvn8jp69q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvn8jp69q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:receipt-x" {...props}></Icon>
