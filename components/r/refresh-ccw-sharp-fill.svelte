<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-yi4adu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq-yi4adu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:refresh-ccw-sharp-fill" {...props}></Icon>
