<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx8zfnwes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx8zfnwes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:information-line" {...props}></Icon>
