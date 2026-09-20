<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wer3vhbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wer3vhbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-brake-worn-linings" {...props}></Icon>
