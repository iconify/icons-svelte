<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-s1ljbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-s1ljbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:medal-star" {...props}></Icon>
