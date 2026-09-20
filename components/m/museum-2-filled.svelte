<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3wndnb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3wndnb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:museum-2-filled" {...props}></Icon>
