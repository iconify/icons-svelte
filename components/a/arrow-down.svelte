<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neyc37j5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="neyc37j5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-down" {...props}></Icon>
