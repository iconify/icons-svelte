<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smu1-736o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="smu1-736o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prosody-light" {...props}></Icon>
