<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvt1tccbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvt1tccbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:psychotherapy-line" {...props}></Icon>
