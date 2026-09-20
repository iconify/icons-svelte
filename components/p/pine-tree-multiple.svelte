<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulk_7v2hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulk_7v2hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pine-tree-multiple" {...props}></Icon>
