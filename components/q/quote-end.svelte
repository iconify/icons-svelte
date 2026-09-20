<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maa29hsla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maa29hsla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:quote-end" {...props}></Icon>
