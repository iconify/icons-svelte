<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew1ze1bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew1ze1bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cream" {...props}></Icon>
