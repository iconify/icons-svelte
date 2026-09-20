<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b08klq9nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b08klq9nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-unordered-list" {...props}></Icon>
