<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on9ysac7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on9ysac7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:corner-up-left" {...props}></Icon>
