<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoc97ab0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoc97ab0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:between-vertical-start" {...props}></Icon>
