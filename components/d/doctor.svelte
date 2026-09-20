<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x85j1tb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x85j1tb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:doctor" {...props}></Icon>
