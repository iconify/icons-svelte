<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz4oqrbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vz4oqrbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-trending-up" {...props}></Icon>
