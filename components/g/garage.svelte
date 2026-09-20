<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxzun484g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxzun484g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:garage" {...props}></Icon>
