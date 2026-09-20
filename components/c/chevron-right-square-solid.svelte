<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv-oe6gwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv-oe6gwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-right-square-solid" {...props}></Icon>
