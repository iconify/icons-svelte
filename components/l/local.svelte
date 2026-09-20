<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxlnq_1on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlnq_1on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:local" {...props}></Icon>
