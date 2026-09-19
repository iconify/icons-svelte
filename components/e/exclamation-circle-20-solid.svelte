<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stzldcb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="stzldcb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:exclamation-circle-20-solid" {...props}></Icon>
