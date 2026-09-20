<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2hgsob8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2hgsob8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:book-reader" {...props}></Icon>
