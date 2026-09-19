<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dahu4cbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="dahu4cbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:nimblr" {...props}></Icon>
