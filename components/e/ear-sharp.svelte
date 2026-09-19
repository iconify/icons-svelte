<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k98tvglog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k98tvglog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ear-sharp" {...props}></Icon>
