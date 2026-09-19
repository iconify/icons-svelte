<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm6s1qwgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pm6s1qwgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:radio" {...props}></Icon>
