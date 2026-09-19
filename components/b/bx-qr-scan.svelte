<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps1rxzboz.css';
import '../../css/n/nug-zhhlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps1rxzboz"/><path class="nug-zhhlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-qr-scan" {...props}></Icon>
