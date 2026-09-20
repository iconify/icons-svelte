<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flmfigpej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="flmfigpej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-boxes-20-solid" {...props}></Icon>
