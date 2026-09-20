<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vis5bn6ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vis5bn6ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:film" {...props}></Icon>
