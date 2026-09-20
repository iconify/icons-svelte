<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of117qg0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="of117qg0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:proposal" {...props}></Icon>
