<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdtvt3bkl.css';
import '../../css/l/l1gaefbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gdtvt3bkl"/><path class="l1gaefbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-boat-48-bold" {...props}></Icon>
