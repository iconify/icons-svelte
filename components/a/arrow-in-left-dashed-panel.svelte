<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn7d8btfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn7d8btfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-left-dashed-panel" {...props}></Icon>
