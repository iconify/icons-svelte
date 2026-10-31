<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c93n78bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c93n78bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bear-fill-round" {...props}></Icon>
