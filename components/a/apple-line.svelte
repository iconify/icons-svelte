<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gddh23byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gddh23byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:apple-line" {...props}></Icon>
