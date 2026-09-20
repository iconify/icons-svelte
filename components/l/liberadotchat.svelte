<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1l9o0bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1l9o0bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:liberadotchat" {...props}></Icon>
