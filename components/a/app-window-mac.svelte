<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/serxxpm-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="serxxpm-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:app-window-mac" {...props}></Icon>
