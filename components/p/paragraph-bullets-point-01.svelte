<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkey5szpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkey5szpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:paragraph-bullets-point-01" {...props}></Icon>
