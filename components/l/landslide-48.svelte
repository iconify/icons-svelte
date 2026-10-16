<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyoe3cbdf.css';
import '../../css/j/jkakw8j_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vyoe3cbdf"/><path class="jkakw8j_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landslide-48" {...props}></Icon>
