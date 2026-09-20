<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj7ba9y9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vj7ba9y9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filameter-light" {...props}></Icon>
