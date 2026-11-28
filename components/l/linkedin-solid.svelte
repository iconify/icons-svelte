<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-65_mbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-65_mbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:linkedin-solid" {...props}></Icon>
