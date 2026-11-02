<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo9placcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo9placcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-search-fill" {...props}></Icon>
