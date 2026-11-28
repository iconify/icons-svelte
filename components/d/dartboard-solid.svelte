<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otmowms0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otmowms0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dartboard-solid" {...props}></Icon>
