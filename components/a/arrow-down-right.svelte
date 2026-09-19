<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7x-4mbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d7x-4mbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-down-right" {...props}></Icon>
