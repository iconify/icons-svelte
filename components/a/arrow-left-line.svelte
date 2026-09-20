<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3do4co6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3do4co6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-left-line" {...props}></Icon>
