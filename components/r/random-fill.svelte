<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfca5tesk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfca5tesk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:random-fill" {...props}></Icon>
