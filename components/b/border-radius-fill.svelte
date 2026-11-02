<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3j59mbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3j59mbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-radius-fill" {...props}></Icon>
