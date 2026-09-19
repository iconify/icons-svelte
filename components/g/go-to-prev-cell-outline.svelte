<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbloa41vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbloa41vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:go-to-prev-cell-outline" {...props}></Icon>
