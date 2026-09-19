<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l74cobbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l74cobbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:person-voice-filled" {...props}></Icon>
