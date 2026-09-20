<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfbiq-b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="sfbiq-b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-vertical-left" {...props}></Icon>
