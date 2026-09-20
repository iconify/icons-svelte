<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm-m9sbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm-m9sbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-j-hexagon-solid" {...props}></Icon>
