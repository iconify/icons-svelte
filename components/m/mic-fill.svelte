<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzekj1ekw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzekj1ekw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mic-fill" {...props}></Icon>
