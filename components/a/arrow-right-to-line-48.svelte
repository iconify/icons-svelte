<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpcq5gb3e.css';
import '../../css/j/j0wasckez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wpcq5gb3e"/><path class="j0wasckez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-to-line-48" {...props}></Icon>
