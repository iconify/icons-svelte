<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-s18fbbr.css';
import '../../css/k/ktyrg6b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x-s18fbbr"/><path class="ktyrg6b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-check-48" {...props}></Icon>
