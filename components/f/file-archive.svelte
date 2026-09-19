<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th45_7bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th45_7bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-archive" {...props}></Icon>
