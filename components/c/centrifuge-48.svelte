<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl-lwcbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sl-lwcbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:centrifuge-48" {...props}></Icon>
