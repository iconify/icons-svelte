<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzxcdvb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jzxcdvb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-left" {...props}></Icon>
