<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tde0x7ylw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tde0x7ylw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cat-fill" {...props}></Icon>
