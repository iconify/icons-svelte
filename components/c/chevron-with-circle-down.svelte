<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdh6xhb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rdh6xhb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-with-circle-down" {...props}></Icon>
