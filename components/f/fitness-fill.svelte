<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em1tzabhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em1tzabhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fitness-fill" {...props}></Icon>
