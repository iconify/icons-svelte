<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlh4vhbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zlh4vhbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:lift-gate-14" {...props}></Icon>
