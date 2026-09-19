<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjpq7ibui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vjpq7ibui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-down-20-solid" {...props}></Icon>
