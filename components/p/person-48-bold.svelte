<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh5m4gk5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sh5m4gk5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:person-48-bold" {...props}></Icon>
