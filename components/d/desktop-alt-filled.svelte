<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv8dltjym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv8dltjym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:desktop-alt-filled" {...props}></Icon>
