<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnr6rb09e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnr6rb09e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:building-04" {...props}></Icon>
