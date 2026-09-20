<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0avj5ukc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0avj5ukc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-info-line" {...props}></Icon>
