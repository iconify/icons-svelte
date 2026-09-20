<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr168oaij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr168oaij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-fill" {...props}></Icon>
