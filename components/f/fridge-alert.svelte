<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-i0e9b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-i0e9b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fridge-alert" {...props}></Icon>
