<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thofd1boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thofd1boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bed" {...props}></Icon>
