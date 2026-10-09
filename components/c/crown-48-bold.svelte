<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4vc4jmhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z4vc4jmhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crown-48-bold" {...props}></Icon>
