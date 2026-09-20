<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czcl3gbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czcl3gbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart-large3" {...props}></Icon>
