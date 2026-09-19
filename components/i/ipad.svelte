<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdolti6_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="mdolti6_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ipad" {...props}></Icon>
