<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwo9clbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwo9clbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coin-line" {...props}></Icon>
