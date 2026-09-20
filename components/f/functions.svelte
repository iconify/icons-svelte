<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccq24fzrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccq24fzrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:functions" {...props}></Icon>
