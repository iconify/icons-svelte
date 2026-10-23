<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzxc1dbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzxc1dbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-x" {...props}></Icon>
