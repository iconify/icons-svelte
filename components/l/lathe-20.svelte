<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur3m-8djy.css';
import '../../css/u/uvv6a-b1c.css';
import '../../css/u/ul72h2brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ur3m-8djy"/><path class="uvv6a-b1c"/><path class="ul72h2brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lathe-20" {...props}></Icon>
