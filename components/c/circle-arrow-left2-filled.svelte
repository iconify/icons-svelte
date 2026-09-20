<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph9k6dtye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ph9k6dtye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-left2-filled" {...props}></Icon>
