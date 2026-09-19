<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbf7t6bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bbf7t6bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:everplaces" {...props}></Icon>
