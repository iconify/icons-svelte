<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqwk__1_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqwk__1_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cash-briefcase-bold" {...props}></Icon>
