<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz0n7hbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz0n7hbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-right-fill" {...props}></Icon>
