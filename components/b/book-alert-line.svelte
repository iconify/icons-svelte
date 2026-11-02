<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr19wtb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr19wtb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-alert-line" {...props}></Icon>
