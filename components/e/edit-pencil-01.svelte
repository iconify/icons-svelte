<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccge8ybny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccge8ybny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:edit-pencil-01" {...props}></Icon>
