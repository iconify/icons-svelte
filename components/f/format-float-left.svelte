<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfrx75qts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfrx75qts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-float-left" {...props}></Icon>
