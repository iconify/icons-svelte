<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m64kke5dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m64kke5dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opendns-light" {...props}></Icon>
