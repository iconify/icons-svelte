<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh23dybnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh23dybnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:figure-fill" {...props}></Icon>
