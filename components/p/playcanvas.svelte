<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea__fodio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea__fodio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:playcanvas" {...props}></Icon>
