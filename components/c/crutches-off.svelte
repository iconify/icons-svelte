<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy0pchbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy0pchbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crutches-off" {...props}></Icon>
