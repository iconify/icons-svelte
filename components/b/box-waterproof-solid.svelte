<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx1jwkbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zx1jwkbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:box-waterproof-solid" {...props}></Icon>
