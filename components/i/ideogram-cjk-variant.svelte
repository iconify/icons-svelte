<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw6w3b36x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw6w3b36x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ideogram-cjk-variant" {...props}></Icon>
