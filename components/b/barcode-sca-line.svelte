<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om471lbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om471lbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barcode-sca-line" {...props}></Icon>
