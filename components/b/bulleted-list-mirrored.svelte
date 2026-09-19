<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8lhj-qne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g8lhj-qne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bulleted-list-mirrored" {...props}></Icon>
