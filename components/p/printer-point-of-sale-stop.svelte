<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za_62gb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za_62gb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-point-of-sale-stop" {...props}></Icon>
