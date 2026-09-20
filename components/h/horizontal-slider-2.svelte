<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmfebc3mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmfebc3mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:horizontal-slider-2" {...props}></Icon>
