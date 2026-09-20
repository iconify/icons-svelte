<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whqrdobun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whqrdobun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart-filled" {...props}></Icon>
