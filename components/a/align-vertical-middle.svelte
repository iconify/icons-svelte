<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7brs9b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k7brs9b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:align-vertical-middle" {...props}></Icon>
