<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7svacbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7svacbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lens-convex-line" {...props}></Icon>
