<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bls7y0bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bls7y0bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cookie" {...props}></Icon>
