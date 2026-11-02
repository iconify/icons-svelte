<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i62i4obqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i62i4obqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brackets-angle-fill" {...props}></Icon>
