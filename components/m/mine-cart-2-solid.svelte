<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuw4xv0mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vuw4xv0mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:mine-cart-2-solid" {...props}></Icon>
