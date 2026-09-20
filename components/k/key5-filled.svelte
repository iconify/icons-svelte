<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rox-p-bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rox-p-bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:key5-filled" {...props}></Icon>
