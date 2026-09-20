<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsw-4vbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsw-4vbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mouse4-filled" {...props}></Icon>
