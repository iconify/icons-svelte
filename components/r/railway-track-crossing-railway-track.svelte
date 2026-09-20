<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwq1znuml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zwq1znuml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:railway-track-crossing-railway-track" {...props}></Icon>
