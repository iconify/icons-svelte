<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th5u_7n9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="th5u_7n9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:google-hangouts" {...props}></Icon>
