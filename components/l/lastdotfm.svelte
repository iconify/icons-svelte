<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v84ai0bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v84ai0bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lastdotfm" {...props}></Icon>
