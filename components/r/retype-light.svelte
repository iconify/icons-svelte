<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik95tthsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ik95tthsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:retype-light" {...props}></Icon>
