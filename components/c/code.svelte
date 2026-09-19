<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhq6yjbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1500,"height":1000};
const content = `<path class="uhq6yjbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:code" {...props}></Icon>
