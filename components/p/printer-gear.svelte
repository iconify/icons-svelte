<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t218p1beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t218p1beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:printer-gear" {...props}></Icon>
