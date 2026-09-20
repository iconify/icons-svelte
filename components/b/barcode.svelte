<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp6wu9boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp6wu9boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:barcode" {...props}></Icon>
