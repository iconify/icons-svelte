<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcdmmlb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcdmmlb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bank-line" {...props}></Icon>
