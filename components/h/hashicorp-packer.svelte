<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvt9z9bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rvt9z9bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-packer" {...props}></Icon>
