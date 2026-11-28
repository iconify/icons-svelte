<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3t04tbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3t04tbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:air-conditioner-check" {...props}></Icon>
