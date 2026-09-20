<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk8c4eb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hk8c4eb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lldap" {...props}></Icon>
