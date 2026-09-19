<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhvmqfbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhvmqfbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:folder-plus" {...props}></Icon>
