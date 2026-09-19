<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weqv4ab8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="weqv4ab8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:email" {...props}></Icon>
