<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6qe8n8xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f6qe8n8xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:css-fill-12" {...props}></Icon>
