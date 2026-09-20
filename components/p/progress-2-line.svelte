<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfln1p-mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfln1p-mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-2-line" {...props}></Icon>
