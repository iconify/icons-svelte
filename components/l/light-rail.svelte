<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv-3p-s8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dv-3p-s8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:light-rail" {...props}></Icon>
