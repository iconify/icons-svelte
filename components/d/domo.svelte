<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si58bs_sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si58bs_sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:domo" {...props}></Icon>
