<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtoh-yx4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtoh-yx4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-plus-circle" {...props}></Icon>
