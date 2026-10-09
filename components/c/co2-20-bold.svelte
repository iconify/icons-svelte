<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifignib1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ifignib1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-20-bold" {...props}></Icon>
