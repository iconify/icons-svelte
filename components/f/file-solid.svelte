<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwjqdwbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwjqdwbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:file-solid" {...props}></Icon>
