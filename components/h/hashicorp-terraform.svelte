<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw1vftp4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gw1vftp4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-terraform" {...props}></Icon>
