<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w66kkxbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w66kkxbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-nigeria-2-fill" {...props}></Icon>
