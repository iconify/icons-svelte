<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6xkzccio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6xkzccio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:goaccess" {...props}></Icon>
