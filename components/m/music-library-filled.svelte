<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax67n89ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax67n89ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:music-library-filled" {...props}></Icon>
