<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr0t6xbmu.css';
import '../../css/h/hviuulbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yr0t6xbmu"/><path class="hviuulbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:beer-20-bold" {...props}></Icon>
