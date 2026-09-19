<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srxqlybhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="srxqlybhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:minus-sm" {...props}></Icon>
