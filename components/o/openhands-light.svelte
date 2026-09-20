<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8ii04yqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8ii04yqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openhands-light" {...props}></Icon>
