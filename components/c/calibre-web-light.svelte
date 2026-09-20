<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we8ztxbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="we8ztxbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calibre-web-light" {...props}></Icon>
