<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i80je-abe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i80je-abe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:cloudflare" {...props}></Icon>
