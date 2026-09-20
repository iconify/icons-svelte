<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgq6q4bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgq6q4bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:info-square-filled" {...props}></Icon>
