<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufc9a5bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufc9a5bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-down" {...props}></Icon>
