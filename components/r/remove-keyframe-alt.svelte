<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl3476bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl3476bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:remove-keyframe-alt" {...props}></Icon>
