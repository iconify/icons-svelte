<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy96p8bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy96p8bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:btcmt" {...props}></Icon>
