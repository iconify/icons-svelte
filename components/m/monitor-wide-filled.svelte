<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdbetmb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdbetmb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:monitor-wide-filled" {...props}></Icon>
