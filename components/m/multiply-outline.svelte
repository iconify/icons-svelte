<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbmv7io-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbmv7io-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:multiply-outline" {...props}></Icon>
