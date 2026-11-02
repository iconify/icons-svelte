<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwp56obhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwp56obhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-plus-line" {...props}></Icon>
