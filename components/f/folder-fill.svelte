<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqzm3-bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqzm3-bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-fill" {...props}></Icon>
