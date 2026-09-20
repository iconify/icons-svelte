<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxcwr8xud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxcwr8xud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-right-bold-box" {...props}></Icon>
