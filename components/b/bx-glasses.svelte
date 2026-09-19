<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w656yrbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w656yrbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-glasses" {...props}></Icon>
