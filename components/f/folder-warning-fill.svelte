<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6a8oybhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6a8oybhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-warning-fill" {...props}></Icon>
