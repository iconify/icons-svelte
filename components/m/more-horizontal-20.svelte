<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikaxoxbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ikaxoxbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:more-horizontal-20" {...props}></Icon>
