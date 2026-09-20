<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn1ih0b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn1ih0b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:globe-cursor-sharp-fill" {...props}></Icon>
