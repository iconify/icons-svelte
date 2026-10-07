<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwnx8bzkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwnx8bzkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alphabet-ethiopic" {...props}></Icon>
