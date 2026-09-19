<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxlyxi02t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cxlyxi02t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-music-fill" {...props}></Icon>
