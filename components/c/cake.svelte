<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/das1e-7xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="das1e-7xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cake" {...props}></Icon>
