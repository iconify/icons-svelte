<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9yakmjwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9yakmjwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hammer-editor-light" {...props}></Icon>
