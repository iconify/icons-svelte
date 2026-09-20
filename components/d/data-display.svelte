<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oer5e_6vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oer5e_6vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:data-display" {...props}></Icon>
