<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy4-pm1pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gy4-pm1pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:behance" {...props}></Icon>
