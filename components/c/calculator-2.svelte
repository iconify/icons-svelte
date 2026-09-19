<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngr1evbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngr1evbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:calculator-2" {...props}></Icon>
