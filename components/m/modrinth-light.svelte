<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgnz_7dgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgnz_7dgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:modrinth-light" {...props}></Icon>
