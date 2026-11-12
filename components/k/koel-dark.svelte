<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h63q1abgr.css';
import '../../css/g/g74ykvjvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h63q1abgr"/><path class="g74ykvjvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:koel-dark" {...props}></Icon>
