<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz2dtsbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yz2dtsbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openldap-dark" {...props}></Icon>
