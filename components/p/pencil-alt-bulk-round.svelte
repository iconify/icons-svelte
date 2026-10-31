<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd-1klc9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd-1klc9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-alt-bulk-round" {...props}></Icon>
