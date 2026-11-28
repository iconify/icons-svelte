<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si738gbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si738gbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-x-solid" {...props}></Icon>
