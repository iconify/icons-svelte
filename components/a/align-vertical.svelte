<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suy8z-box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suy8z-box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:align-vertical" {...props}></Icon>
