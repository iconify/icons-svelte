<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlolk7bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hlolk7bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-cooperative-48-bold" {...props}></Icon>
