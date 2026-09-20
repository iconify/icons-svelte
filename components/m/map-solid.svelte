<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjtwlnbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjtwlnbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:map-solid" {...props}></Icon>
