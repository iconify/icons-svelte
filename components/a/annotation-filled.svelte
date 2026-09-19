<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvwao29ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvwao29ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation-filled" {...props}></Icon>
