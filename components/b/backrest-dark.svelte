<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emhy26btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="emhy26btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:backrest-dark" {...props}></Icon>
