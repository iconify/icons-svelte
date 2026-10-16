<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms_f6iiek.css';
import '../../css/p/pjqmup4lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ms_f6iiek"/><path class="pjqmup4lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:outage-map-20" {...props}></Icon>
