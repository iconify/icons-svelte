<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et8rym2vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="et8rym2vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:drag-vertical-outline" {...props}></Icon>
