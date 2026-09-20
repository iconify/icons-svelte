<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e60u6gbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e60u6gbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor" {...props}></Icon>
