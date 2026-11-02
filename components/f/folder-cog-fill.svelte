<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imzn-ib-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imzn-ib-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-cog-fill" {...props}></Icon>
