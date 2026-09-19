<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxoo1v3ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxoo1v3ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:position" {...props}></Icon>
