<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uds0ssrod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uds0ssrod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-left" {...props}></Icon>
