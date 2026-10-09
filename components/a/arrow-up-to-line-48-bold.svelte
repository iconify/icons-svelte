<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-29nt30n.css';
import '../../css/s/sj5ux4q1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m-29nt30n"/><path class="sj5ux4q1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-to-line-48-bold" {...props}></Icon>
