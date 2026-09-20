<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6pj8kb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6pj8kb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pulse-filled" {...props}></Icon>
