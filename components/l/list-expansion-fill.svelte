<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnss54tzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnss54tzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-expansion-fill" {...props}></Icon>
