<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xra4d6b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xra4d6b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:navigation" {...props}></Icon>
