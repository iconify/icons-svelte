<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu0z4-bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tu0z4-bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cursor-click-solid" {...props}></Icon>
