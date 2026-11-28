<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6qud1_5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6qud1_5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cart-refresh" {...props}></Icon>
