<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asaqchf9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="asaqchf9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aliasvault-light" {...props}></Icon>
