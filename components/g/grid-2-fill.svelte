<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxi646-cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxi646-cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2-fill" {...props}></Icon>
