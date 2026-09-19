<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcjt_w24a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcjt_w24a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-left" {...props}></Icon>
