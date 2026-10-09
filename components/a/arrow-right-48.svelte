<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9t00gb6u.css';
import '../../css/f/fqwpfx1sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x9t00gb6u"/><path class="fqwpfx1sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-48" {...props}></Icon>
