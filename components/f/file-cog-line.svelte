<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdryx6bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdryx6bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-cog-line" {...props}></Icon>
