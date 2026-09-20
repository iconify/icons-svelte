<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5o3pmfii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i5o3pmfii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:navigation-arrow-top-right" {...props}></Icon>
