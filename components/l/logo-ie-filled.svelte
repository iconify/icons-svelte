<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-d-gcptl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-d-gcptl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-ie-filled" {...props}></Icon>
