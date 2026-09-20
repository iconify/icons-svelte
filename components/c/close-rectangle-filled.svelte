<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtoeuobyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtoeuobyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:close-rectangle-filled" {...props}></Icon>
