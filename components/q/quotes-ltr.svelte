<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ombo0mbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ombo0mbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:quotes-ltr" {...props}></Icon>
