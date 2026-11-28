<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov6z5xbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov6z5xbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:clipboard-list-solid" {...props}></Icon>
