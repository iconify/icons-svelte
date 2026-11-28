<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvj5spbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvj5spbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-face-look-right-solid" {...props}></Icon>
