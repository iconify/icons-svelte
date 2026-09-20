<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fer6cd8xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fer6cd8xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-html5" {...props}></Icon>
