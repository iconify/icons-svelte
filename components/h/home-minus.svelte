<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oedbzrzfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oedbzrzfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:home-minus" {...props}></Icon>
