<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4xiqk_0v.css';
import '../../css/o/oo004ivrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4xiqk_0v"/><path class="oo004ivrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-toggle-left" {...props}></Icon>
