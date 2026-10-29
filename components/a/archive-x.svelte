<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvxmwx3yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvxmwx3yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:archive-x" {...props}></Icon>
