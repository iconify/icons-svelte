<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/f/f5ogxjm1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="f5ogxjm1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-bold-duotone" {...props}></Icon>
