<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg5agddeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg5agddeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:desk-01" {...props}></Icon>
