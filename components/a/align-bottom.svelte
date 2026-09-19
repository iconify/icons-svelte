<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv1t2xe7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cv1t2xe7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:align-bottom" {...props}></Icon>
