<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ahils_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-ahils_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-water" {...props}></Icon>
