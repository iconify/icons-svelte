<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur_vkvbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur_vkvbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-stored-data" {...props}></Icon>
