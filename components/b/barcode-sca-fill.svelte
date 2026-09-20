<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t98sw_g9d.css';
import '../../css/q/q2gzyfm-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t98sw_g9d"/><path class="q2gzyfm-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:barcode-sca-fill" {...props}></Icon>
