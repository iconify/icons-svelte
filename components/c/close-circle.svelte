<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7q8mlb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q7q8mlb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:close-circle" {...props}></Icon>
