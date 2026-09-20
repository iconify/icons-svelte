<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8iz7rbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c8iz7rbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:pipeline" {...props}></Icon>
