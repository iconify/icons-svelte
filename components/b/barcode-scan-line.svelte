<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxobjqb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxobjqb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:barcode-scan-line" {...props}></Icon>
