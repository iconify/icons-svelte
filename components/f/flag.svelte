<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ze5rb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2ze5rb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:flag" {...props}></Icon>
