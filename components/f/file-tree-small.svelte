<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndk-6c8er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ndk-6c8er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-tree-small" {...props}></Icon>
