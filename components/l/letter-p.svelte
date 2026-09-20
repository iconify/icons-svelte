<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om7wr648a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om7wr648a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-p" {...props}></Icon>
