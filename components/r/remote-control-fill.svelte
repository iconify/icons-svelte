<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk_n9jbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk_n9jbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:remote-control-fill" {...props}></Icon>
