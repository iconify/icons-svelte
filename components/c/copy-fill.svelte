<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di53g-bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di53g-bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-fill" {...props}></Icon>
