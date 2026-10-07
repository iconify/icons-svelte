<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgvtz8b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgvtz8b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lens-convex" {...props}></Icon>
