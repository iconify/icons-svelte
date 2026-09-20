<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt5tqbcrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt5tqbcrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:green-onion" {...props}></Icon>
