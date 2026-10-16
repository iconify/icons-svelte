<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaet4wb5s.css';
import '../../css/a/ape_a0b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iaet4wb5s"/><path class="ape_a0b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:code-block-48-bold" {...props}></Icon>
