<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfnojhbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfnojhbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:grid-solid" {...props}></Icon>
