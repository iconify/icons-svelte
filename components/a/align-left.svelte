<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi65ewbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bi65ewbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:align-left" {...props}></Icon>
