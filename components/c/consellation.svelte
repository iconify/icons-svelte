<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnh3mtb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnh3mtb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:consellation" {...props}></Icon>
