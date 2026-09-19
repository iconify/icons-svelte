<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjf65-bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zjf65-bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:italic-20-solid" {...props}></Icon>
