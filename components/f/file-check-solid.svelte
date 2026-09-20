<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4r117byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4r117byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:file-check-solid" {...props}></Icon>
