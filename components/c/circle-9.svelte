<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ars639bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ars639bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:circle-9" {...props}></Icon>
