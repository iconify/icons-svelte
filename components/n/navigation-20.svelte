<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvo5b-0za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nvo5b-0za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:navigation-20" {...props}></Icon>
