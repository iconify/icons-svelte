<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0e9-g4hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0e9-g4hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:funnel-outline" {...props}></Icon>
