<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0jst6b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e0jst6b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cc-text-above-caption" {...props}></Icon>
