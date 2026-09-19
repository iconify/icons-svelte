<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg-uzcb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg-uzcb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:chevron-up" {...props}></Icon>
