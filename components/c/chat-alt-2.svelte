<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr4gv3myf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr4gv3myf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chat-alt-2" {...props}></Icon>
