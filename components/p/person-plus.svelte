<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bct70fbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bct70fbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:person-plus" {...props}></Icon>
