<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv97fzbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv97fzbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fuel-cell" {...props}></Icon>
