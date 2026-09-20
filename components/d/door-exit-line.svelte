<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaubn2bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaubn2bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:door-exit-line" {...props}></Icon>
