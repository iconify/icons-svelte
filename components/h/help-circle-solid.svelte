<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_we9ubre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_we9ubre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:help-circle-solid" {...props}></Icon>
