<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr4tues1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sr4tues1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:air" {...props}></Icon>
