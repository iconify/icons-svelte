<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm9zwacvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm9zwacvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-minus" {...props}></Icon>
