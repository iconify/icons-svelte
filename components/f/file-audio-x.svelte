<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo90mb9-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo90mb9-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-audio-x" {...props}></Icon>
