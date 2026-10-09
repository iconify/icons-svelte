<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax49_hbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ax49_hbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-right-48" {...props}></Icon>
