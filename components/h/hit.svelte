<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8d2ivbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8d2ivbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hit" {...props}></Icon>
