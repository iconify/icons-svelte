<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbx_tybht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbx_tybht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diamond-24" {...props}></Icon>
