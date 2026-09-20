<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce11zyode.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce11zyode"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-nfc" {...props}></Icon>
