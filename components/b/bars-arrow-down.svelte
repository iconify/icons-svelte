<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow7yq4bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ow7yq4bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bars-arrow-down" {...props}></Icon>
