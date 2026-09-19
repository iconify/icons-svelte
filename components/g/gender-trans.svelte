<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df41reb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="df41reb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:gender-trans" {...props}></Icon>
