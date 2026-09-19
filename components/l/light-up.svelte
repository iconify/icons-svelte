<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx7416blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hx7416blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:light-up" {...props}></Icon>
