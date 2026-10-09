<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isno3kbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="isno3kbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bird-48-bold" {...props}></Icon>
