<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz2z0-b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz2z0-b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:exit-fullscreen-circle-filled" {...props}></Icon>
