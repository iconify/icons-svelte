<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chob2xo_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chob2xo_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:key-round-plus" {...props}></Icon>
