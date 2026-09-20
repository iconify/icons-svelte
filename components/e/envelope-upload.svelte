<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp2_cybfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp2_cybfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-upload" {...props}></Icon>
