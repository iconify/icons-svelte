<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdvu4gb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdvu4gb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:penis-outline-24px" {...props}></Icon>
