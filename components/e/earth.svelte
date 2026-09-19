<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viuap04qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="viuap04qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:earth" {...props}></Icon>
