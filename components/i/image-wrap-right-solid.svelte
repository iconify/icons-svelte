<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpqqzbcur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpqqzbcur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-wrap-right-solid" {...props}></Icon>
