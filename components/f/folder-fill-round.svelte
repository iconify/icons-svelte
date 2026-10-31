<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qihsy-s8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qihsy-s8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-fill-round" {...props}></Icon>
