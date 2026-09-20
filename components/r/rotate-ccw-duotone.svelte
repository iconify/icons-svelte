<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqlz9tzcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqlz9tzcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rotate-ccw-duotone" {...props}></Icon>
