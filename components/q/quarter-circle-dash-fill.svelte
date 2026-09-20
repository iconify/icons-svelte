<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdyz09b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdyz09b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quarter-circle-dash-fill" {...props}></Icon>
