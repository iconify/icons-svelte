<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aibzmo8rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="aibzmo8rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-holding" {...props}></Icon>
