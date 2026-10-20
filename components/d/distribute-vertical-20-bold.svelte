<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8n4llp5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b8n4llp5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:distribute-vertical-20-bold" {...props}></Icon>
