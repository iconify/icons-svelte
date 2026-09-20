<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m98lz0v9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m98lz0v9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:carrot" {...props}></Icon>
