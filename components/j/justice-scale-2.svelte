<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixku2sbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixku2sbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:justice-scale-2" {...props}></Icon>
