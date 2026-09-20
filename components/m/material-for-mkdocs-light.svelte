<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6-lcumwc.css';
import '../../css/q/q6r9cfypp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j6-lcumwc"/><path class="q6r9cfypp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:material-for-mkdocs-light" {...props}></Icon>
