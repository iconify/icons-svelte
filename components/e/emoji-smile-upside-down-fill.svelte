<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df6l_sv9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="df6l_sv9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-smile-upside-down-fill" {...props}></Icon>
