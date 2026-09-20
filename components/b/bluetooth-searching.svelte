<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7rz6lbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7rz6lbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bluetooth-searching" {...props}></Icon>
