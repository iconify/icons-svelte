<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek1kss65i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek1kss65i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-adwords" {...props}></Icon>
