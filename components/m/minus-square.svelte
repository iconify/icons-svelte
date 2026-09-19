<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peafspbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peafspbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:minus-square" {...props}></Icon>
