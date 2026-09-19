<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swk7trbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="swk7trbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:history" {...props}></Icon>
