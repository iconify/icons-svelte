<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s28b8lbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s28b8lbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-up-left-solid" {...props}></Icon>
