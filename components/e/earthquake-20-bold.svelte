<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gclpr8i1a.css';
import '../../css/r/royu2xbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gclpr8i1a"/><path class="royu2xbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earthquake-20-bold" {...props}></Icon>
