<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2y6jdb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2y6jdb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-circle-line" {...props}></Icon>
