<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc3j3dfwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc3j3dfwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-check" {...props}></Icon>
