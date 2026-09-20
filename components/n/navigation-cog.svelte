<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai9nbibbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai9nbibbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-cog" {...props}></Icon>
