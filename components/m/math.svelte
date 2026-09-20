<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwoutw7cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwoutw7cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:math" {...props}></Icon>
