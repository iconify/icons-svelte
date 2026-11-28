<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ema1yjb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ema1yjb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:person" {...props}></Icon>
