<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3wq8n-yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s3wq8n-yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:rocket" {...props}></Icon>
