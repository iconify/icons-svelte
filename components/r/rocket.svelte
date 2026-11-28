<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz6k6rb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz6k6rb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:rocket" {...props}></Icon>
