<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvyv4v4qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvyv4v4qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-4-line" {...props}></Icon>
