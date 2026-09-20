<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oewliqb1a.css';
import '../../css/c/cc1vgdb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oewliqb1a"/><path class="cc1vgdb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:meter-high-16" {...props}></Icon>
