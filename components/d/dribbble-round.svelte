<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpsy1qb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpsy1qb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dribbble-round" {...props}></Icon>
