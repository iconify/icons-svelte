<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk01w1bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dk01w1bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:dots-three-horizontal" {...props}></Icon>
