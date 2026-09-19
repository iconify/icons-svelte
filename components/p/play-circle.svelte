<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hodzw-baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hodzw-baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:play-circle" {...props}></Icon>
