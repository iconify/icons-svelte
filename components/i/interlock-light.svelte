<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shhm08woh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shhm08woh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:interlock-light" {...props}></Icon>
