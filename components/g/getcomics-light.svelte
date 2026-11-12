<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hexzpob7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hexzpob7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:getcomics-light" {...props}></Icon>
