<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgangomwz.css';
import '../../css/d/d1ft4ebeo.css';
import '../../css/d/dn6qqpqrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hgangomwz"/><path class="d1ft4ebeo"/><path class="dn6qqpqrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-contacts-light" {...props}></Icon>
