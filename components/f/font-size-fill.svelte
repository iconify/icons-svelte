<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww2l8eq6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww2l8eq6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:font-size-fill" {...props}></Icon>
