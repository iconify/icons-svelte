<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saw8iqbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saw8iqbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pentagon" {...props}></Icon>
