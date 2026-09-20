<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkd-rr4pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkd-rr4pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plane-takeoff" {...props}></Icon>
