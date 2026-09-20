<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhtdthmab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhtdthmab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:barrier-up" {...props}></Icon>
