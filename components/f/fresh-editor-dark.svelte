<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk1sao3wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uk1sao3wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fresh-editor-dark" {...props}></Icon>
