<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzb44pixj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzb44pixj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:octagon-filled" {...props}></Icon>
