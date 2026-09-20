<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnjwg-b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wnjwg-b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:color-swatches-solid" {...props}></Icon>
