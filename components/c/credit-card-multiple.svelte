<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hff65g63h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="hff65g63h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:credit-card-multiple" {...props}></Icon>
