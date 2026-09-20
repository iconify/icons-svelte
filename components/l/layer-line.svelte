<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6vvt1b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6vvt1b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layer-line" {...props}></Icon>
