<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxb66cbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxb66cbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-rainstorm-line" {...props}></Icon>
