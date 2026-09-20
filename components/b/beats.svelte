<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkt24s-up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkt24s-up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:beats" {...props}></Icon>
