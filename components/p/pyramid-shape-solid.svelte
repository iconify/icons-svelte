<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-mrup4sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m-mrup4sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pyramid-shape-solid" {...props}></Icon>
