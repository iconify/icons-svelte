<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulg-93b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulg-93b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fact-check-filled" {...props}></Icon>
