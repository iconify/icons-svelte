<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrsh86agt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrsh86agt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flame" {...props}></Icon>
