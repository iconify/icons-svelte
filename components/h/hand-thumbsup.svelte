<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa6yx-bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wa6yx-bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hand-thumbsup" {...props}></Icon>
