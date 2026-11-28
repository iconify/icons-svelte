<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc5f-1r2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc5f-1r2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:basket-heart" {...props}></Icon>
