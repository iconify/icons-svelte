<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmkjnmtxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmkjnmtxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-packer-dark" {...props}></Icon>
