<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfeh86b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfeh86b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:alert" {...props}></Icon>
