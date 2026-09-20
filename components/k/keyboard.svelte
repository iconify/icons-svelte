<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_za0_bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_za0_bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:keyboard" {...props}></Icon>
