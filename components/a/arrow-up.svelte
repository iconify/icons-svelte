<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do9oiybzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="do9oiybzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-up" {...props}></Icon>
