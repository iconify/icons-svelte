<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt5-h7irr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bt5-h7irr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:calendar" {...props}></Icon>
