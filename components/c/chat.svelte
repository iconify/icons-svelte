<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2utsd-fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2utsd-fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:chat" {...props}></Icon>
