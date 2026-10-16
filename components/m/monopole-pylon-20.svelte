<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojf58obzl.css';
import '../../css/z/zi9baroae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ojf58obzl"/><path class="zi9baroae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monopole-pylon-20" {...props}></Icon>
