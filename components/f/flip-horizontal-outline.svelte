<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z38k6nb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z38k6nb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:flip-horizontal-outline" {...props}></Icon>
