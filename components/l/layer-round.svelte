<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig76nw-0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig76nw-0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layer-round" {...props}></Icon>
