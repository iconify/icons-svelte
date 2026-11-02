<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_4-tccpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_4-tccpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-incoming-line" {...props}></Icon>
