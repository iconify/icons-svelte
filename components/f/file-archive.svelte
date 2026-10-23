<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drn0rjbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drn0rjbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-archive" {...props}></Icon>
