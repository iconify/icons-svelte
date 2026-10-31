<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw_p5en_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw_p5en_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-close-fill-round" {...props}></Icon>
