<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzuwc8bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzuwc8bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:functions-1" {...props}></Icon>
