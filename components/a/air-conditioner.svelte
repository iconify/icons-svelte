<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whznf4bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whznf4bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:air-conditioner" {...props}></Icon>
