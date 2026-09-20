<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeq0uvb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yeq0uvb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:grid-small" {...props}></Icon>
