<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0iqd7bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0iqd7bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:barcode" {...props}></Icon>
