<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h52p0wbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h52p0wbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lamp3-filled" {...props}></Icon>
