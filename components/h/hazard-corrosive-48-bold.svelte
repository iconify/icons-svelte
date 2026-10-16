<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2mjsubix.css';
import '../../css/a/a_eufztoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h2mjsubix"/><path class="a_eufztoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-corrosive-48-bold" {...props}></Icon>
