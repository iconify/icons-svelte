<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4xae4spt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4xae4spt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-thick-up-4-bold" {...props}></Icon>
