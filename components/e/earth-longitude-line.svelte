<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy0sp0bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy0sp0bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-longitude-line" {...props}></Icon>
