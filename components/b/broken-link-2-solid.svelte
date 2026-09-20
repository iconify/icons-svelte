<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrn7oxbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jrn7oxbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:broken-link-2-solid" {...props}></Icon>
