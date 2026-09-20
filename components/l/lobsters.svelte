<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktzlyebwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktzlyebwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lobsters" {...props}></Icon>
