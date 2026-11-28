<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djseinb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djseinb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-audio-solid" {...props}></Icon>
