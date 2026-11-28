<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtuchbc2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtuchbc2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-minus-solid" {...props}></Icon>
