<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubob10ayu.css';
import '../../css/t/tl4woi6ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubob10ayu"/><path class="tl4woi6ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:medal" {...props}></Icon>
