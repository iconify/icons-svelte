<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fws7bbc5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fws7bbc5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bridge" {...props}></Icon>
