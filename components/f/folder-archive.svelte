<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5n2x1bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5n2x1bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:folder-archive" {...props}></Icon>
