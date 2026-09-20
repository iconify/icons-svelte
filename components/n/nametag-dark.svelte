<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym51ckbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ym51ckbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nametag-dark" {...props}></Icon>
