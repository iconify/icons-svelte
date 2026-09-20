<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz11d19xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vz11d19xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:jump-16" {...props}></Icon>
