<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1-30ib3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1-30ib3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:image-minus" {...props}></Icon>
