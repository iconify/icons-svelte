<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb3conbjb.css';
import '../../css/x/x1p0svkkr.css';
import '../../css/b/bf52ribiq.css';
import '../../css/x/x3z57-byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bb3conbjb"/><path class="x1p0svkkr"/><path class="bf52ribiq"/><path class="x3z57-byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-queue-48-bold" {...props}></Icon>
