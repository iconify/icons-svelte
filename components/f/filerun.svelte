<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-gr0fbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-gr0fbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filerun" {...props}></Icon>
