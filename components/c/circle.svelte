<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz3wsbcfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pz3wsbcfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:circle" {...props}></Icon>
