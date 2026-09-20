<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvya7xl9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvya7xl9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bnb-line" {...props}></Icon>
