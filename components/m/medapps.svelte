<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_3gsznsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="f_3gsznsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:medapps" {...props}></Icon>
