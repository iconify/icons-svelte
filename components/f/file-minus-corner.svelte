<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nql205rcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nql205rcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-minus-corner" {...props}></Icon>
