<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akoau_biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akoau_biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:fiverr-filled" {...props}></Icon>
