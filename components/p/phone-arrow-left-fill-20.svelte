<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2j72gzuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f2j72gzuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-arrow-left-fill-20" {...props}></Icon>
