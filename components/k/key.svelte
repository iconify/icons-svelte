<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt591tbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt591tbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:key" {...props}></Icon>
