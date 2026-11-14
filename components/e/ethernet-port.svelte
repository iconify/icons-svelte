<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u721d8zll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u721d8zll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ethernet-port" {...props}></Icon>
