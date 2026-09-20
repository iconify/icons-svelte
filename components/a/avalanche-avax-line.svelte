<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ola4pci0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ola4pci0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:avalanche-avax-line" {...props}></Icon>
