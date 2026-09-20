<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7qys9bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7qys9bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arc-browser-fill" {...props}></Icon>
