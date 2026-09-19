<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf4lu5bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cf4lu5bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flag-o" {...props}></Icon>
