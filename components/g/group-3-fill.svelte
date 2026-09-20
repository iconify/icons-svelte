<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7-9x2bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7-9x2bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:group-3-fill" {...props}></Icon>
