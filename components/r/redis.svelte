<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fox_q4z8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fox_q4z8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:redis" {...props}></Icon>
