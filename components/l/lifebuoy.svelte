<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv797gbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wv797gbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:lifebuoy" {...props}></Icon>
