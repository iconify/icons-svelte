<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddebkccpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddebkccpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-search-fill" {...props}></Icon>
