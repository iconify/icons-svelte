<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbihy7btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbihy7btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:columns" {...props}></Icon>
