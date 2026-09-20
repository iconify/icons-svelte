<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuc0bcbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuc0bcbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-text-fill" {...props}></Icon>
