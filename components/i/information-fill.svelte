<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs93ev7th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs93ev7th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:information-fill" {...props}></Icon>
