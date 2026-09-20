<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb_s1xbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb_s1xbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hair-2-fill" {...props}></Icon>
