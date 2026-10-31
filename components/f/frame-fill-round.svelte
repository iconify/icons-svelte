<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru2dtsixs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru2dtsixs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:frame-fill-round" {...props}></Icon>
