<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgmc37r6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hgmc37r6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:leaf" {...props}></Icon>
