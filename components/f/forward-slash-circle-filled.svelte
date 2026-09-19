<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0f8p3u2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0f8p3u2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:forward-slash-circle-filled" {...props}></Icon>
