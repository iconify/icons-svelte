<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8mc9p7aq.css';
import '../../css/w/wlmt3rjgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8mc9p7aq"/><path class="wlmt3rjgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image" {...props}></Icon>
