<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny63qj1dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny63qj1dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:horizontal-split" {...props}></Icon>
