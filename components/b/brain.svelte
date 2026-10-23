<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol-8m8bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol-8m8bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:brain" {...props}></Icon>
