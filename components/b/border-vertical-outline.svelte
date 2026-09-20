<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeo4x-vgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qeo4x-vgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-vertical-outline" {...props}></Icon>
