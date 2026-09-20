<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2db6qbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2db6qbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-2-box-multiple" {...props}></Icon>
