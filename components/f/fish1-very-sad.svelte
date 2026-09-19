<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0wc70byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s0wc70byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish1-very-sad" {...props}></Icon>
