<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8uw9yb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8uw9yb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-6" {...props}></Icon>
