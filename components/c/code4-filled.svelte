<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhdaigbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhdaigbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:code4-filled" {...props}></Icon>
