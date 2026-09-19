<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6i4w3bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="a6i4w3bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:h3-20-solid" {...props}></Icon>
