<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e94cj6bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e94cj6bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-minus-filled" {...props}></Icon>
