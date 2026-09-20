<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc_d3616n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc_d3616n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mcdonald-s" {...props}></Icon>
