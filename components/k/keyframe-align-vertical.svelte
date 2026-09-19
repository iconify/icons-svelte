<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq0jm3byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq0jm3byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:keyframe-align-vertical" {...props}></Icon>
