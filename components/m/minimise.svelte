<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olol1g_ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="olol1g_ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:minimise" {...props}></Icon>
