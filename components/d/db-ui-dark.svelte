<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf7_-71-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qf7_-71-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:db-ui-dark" {...props}></Icon>
