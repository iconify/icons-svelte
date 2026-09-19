<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inl1udblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="inl1udblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chevron-right" {...props}></Icon>
