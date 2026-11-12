<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbhmpbcfb.css';
import '../../css/t/t_72od1sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dbhmpbcfb"/><path class="t_72od1sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aliexpress-light" {...props}></Icon>
