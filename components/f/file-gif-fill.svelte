<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pokm4jbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pokm4jbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-gif-fill" {...props}></Icon>
