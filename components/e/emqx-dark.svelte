<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmlwj9fmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmlwj9fmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emqx-dark" {...props}></Icon>
