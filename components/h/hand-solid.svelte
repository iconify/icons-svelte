<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geex6gb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geex6gb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hand-solid" {...props}></Icon>
