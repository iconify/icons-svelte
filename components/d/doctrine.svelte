<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc0cf7bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc0cf7bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:doctrine" {...props}></Icon>
