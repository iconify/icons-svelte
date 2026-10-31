<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oclkglb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oclkglb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-search-round" {...props}></Icon>
