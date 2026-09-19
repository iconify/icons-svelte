<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiqa0nbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiqa0nbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:home" {...props}></Icon>
