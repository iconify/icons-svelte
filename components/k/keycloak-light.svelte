<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0a-z351k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0a-z351k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:keycloak-light" {...props}></Icon>
