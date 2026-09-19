<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxuijpbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxuijpbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bread-filled" {...props}></Icon>
