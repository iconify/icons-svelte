<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eteriv24p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eteriv24p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fold-horizontal-solid" {...props}></Icon>
