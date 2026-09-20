<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q20fa9mbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q20fa9mbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-redo" {...props}></Icon>
