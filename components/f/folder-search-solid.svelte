<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exjkiwm5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exjkiwm5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-search-solid" {...props}></Icon>
