<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcjrcrbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcjrcrbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:big-ben-line" {...props}></Icon>
