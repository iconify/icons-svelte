<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9u-0nb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l9u-0nb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-circle-20-solid" {...props}></Icon>
