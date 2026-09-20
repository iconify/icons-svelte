<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbd7ul27k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qbd7ul27k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:checkmk-dark" {...props}></Icon>
