<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1kymxbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1kymxbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:magnifying-glass-circle" {...props}></Icon>
