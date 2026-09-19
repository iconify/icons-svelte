<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nas_g6c0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nas_g6c0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:list-minus" {...props}></Icon>
