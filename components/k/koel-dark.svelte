<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgjfb3mbd.css';
import '../../css/g/g74ykvjvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tgjfb3mbd"/><path class="g74ykvjvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:koel-dark" {...props}></Icon>
