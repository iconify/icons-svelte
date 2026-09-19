<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqu2aeb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mqu2aeb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:creative-commons-noncommercial-eu" {...props}></Icon>
