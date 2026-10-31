<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j021hccwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j021hccwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-left-right-gloss" {...props}></Icon>
