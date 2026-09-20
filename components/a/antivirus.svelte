<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6gyts6an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6gyts6an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:antivirus" {...props}></Icon>
