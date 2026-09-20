<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py9infbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py9infbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rewind-line" {...props}></Icon>
