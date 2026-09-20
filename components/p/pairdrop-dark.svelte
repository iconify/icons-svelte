<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z09i_33ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z09i_33ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pairdrop-dark" {...props}></Icon>
