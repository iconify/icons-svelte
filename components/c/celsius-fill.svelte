<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsme-bm6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsme-bm6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:celsius-fill" {...props}></Icon>
