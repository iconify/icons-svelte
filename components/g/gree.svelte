<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6i8h_b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":618,"height":704};
const content = `<path class="w6i8h_b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:gree" {...props}></Icon>
