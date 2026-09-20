<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6ui7xiyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6ui7xiyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:math-integral-box" {...props}></Icon>
