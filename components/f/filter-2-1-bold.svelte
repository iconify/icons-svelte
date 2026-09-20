<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5l0mll-q.css';
import '../../css/p/pil8ifblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5l0mll-q"/><path class="pil8ifblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:filter-2-1-bold" {...props}></Icon>
