<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_o8orwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3_o8orwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:play" {...props}></Icon>
