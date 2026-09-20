<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6af0vbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6af0vbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:guy-fawkes-mask" {...props}></Icon>
