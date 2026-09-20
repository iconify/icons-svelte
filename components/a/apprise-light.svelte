<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuidnrg9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fuidnrg9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apprise-light" {...props}></Icon>
