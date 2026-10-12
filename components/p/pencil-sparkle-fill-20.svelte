<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4e8n_k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h4e8n_k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pencil-sparkle-fill-20" {...props}></Icon>
