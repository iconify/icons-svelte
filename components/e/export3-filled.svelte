<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6drkibnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6drkibnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:export3-filled" {...props}></Icon>
