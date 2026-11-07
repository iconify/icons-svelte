<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv2ikpz9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv2ikpz9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filters-linear" {...props}></Icon>
