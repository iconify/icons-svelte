<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djvzlmb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="djvzlmb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:key" {...props}></Icon>
