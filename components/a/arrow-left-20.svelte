<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oawkc0bme.css';
import '../../css/y/ypair_oeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oawkc0bme"/><path class="ypair_oeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-20" {...props}></Icon>
