<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmewf005f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmewf005f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:earth-pin-2-bold" {...props}></Icon>
