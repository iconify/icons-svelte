<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt7xkpbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rt7xkpbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:enclosed" {...props}></Icon>
