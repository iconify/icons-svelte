<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp-bh0rxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mp-bh0rxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pswd-light" {...props}></Icon>
