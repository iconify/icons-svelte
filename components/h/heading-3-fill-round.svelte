<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpgk-5brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpgk-5brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-3-fill-round" {...props}></Icon>
