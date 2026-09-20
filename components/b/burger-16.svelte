<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3ttebb7p.css';
import '../../css/k/km_nv7h3m.css';
import '../../css/l/lahok-bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e3ttebb7p"/><path class="km_nv7h3m"/><path class="lahok-bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:burger-16" {...props}></Icon>
