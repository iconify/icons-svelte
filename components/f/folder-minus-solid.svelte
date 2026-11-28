<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gar376luf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gar376luf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-minus-solid" {...props}></Icon>
