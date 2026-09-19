<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnvec2uhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tnvec2uhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:progress-empty" {...props}></Icon>
