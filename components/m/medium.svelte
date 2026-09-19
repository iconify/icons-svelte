<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu5ad5q4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu5ad5q4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:medium" {...props}></Icon>
