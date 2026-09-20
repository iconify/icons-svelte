<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j99qagbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j99qagbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:borg-dark" {...props}></Icon>
