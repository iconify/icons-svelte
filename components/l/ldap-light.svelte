<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipihkyb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ipihkyb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ldap-light" {...props}></Icon>
