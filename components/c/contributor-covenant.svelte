<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_q5fvoit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_q5fvoit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:contributor-covenant" {...props}></Icon>
