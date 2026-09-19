<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyk3-1bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyk3-1bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:cross" {...props}></Icon>
