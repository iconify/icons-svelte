<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deeui2chz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="deeui2chz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:mine-cart-2-remix" {...props}></Icon>
