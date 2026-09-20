<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8j-lcrbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8j-lcrbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:diff" {...props}></Icon>
