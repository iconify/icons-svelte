<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqr6emsqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqr6emsqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-variant-minus" {...props}></Icon>
