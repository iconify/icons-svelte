<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehy36_bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehy36_bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:fi" {...props}></Icon>
