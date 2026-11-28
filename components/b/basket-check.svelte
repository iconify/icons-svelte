<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxh-a_buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxh-a_buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:basket-check" {...props}></Icon>
