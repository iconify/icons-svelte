<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr-6avbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr-6avbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-reverse-fill" {...props}></Icon>
