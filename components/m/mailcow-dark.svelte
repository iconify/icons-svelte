<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uotgo6lhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uotgo6lhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailcow-dark" {...props}></Icon>
