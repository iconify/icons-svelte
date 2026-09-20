<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpa4lnb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpa4lnb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:barcode-duotone" {...props}></Icon>
