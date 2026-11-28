<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew582eu4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew582eu4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:columns-4-solid" {...props}></Icon>
