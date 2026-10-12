<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc0h-ybnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc0h-ybnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:arrow-big-left-dash-filled" {...props}></Icon>
