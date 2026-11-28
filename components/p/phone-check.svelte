<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe-55h6zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe-55h6zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:phone-check" {...props}></Icon>
