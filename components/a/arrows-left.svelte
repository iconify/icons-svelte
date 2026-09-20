<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr1-xddal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dr1-xddal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrows-left" {...props}></Icon>
