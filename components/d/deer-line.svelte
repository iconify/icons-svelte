<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay418-bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay418-bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:deer-line" {...props}></Icon>
