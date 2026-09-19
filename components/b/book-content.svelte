<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do0-t4b8n.css';
import '../../css/q/qf6fzcbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do0-t4b8n"/><path class="qf6fzcbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:book-content" {...props}></Icon>
