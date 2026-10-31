<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgyv-v2ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dgyv-v2ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:italic-slash-20-solid" {...props}></Icon>
