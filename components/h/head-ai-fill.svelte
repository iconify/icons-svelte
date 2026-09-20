<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4mcejd1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4mcejd1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:head-ai-fill" {...props}></Icon>
