<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhot0ixic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhot0ixic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:list-demand" {...props}></Icon>
