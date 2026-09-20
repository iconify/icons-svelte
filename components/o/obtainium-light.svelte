<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuso3kbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uuso3kbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obtainium-light" {...props}></Icon>
