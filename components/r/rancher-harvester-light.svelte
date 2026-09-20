<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-pg133zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v-pg133zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-harvester-light" {...props}></Icon>
