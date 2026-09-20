<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-77o_bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-77o_bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forward-square-filled" {...props}></Icon>
