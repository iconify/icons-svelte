<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dowh2zbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dowh2zbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-10-box-multiple" {...props}></Icon>
