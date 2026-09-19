<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elwcdkbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="elwcdkbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paper-clip-20-solid" {...props}></Icon>
