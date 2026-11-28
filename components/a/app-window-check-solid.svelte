<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj2nvgblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj2nvgblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:app-window-check-solid" {...props}></Icon>
