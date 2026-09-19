<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrd3ofbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrd3ofbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrange-by-letters-a-z" {...props}></Icon>
