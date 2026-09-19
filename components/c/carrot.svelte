<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylacaac8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ylacaac8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:carrot" {...props}></Icon>
